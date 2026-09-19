<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1zkl6b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1zkl6b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain" {...props}></Icon>
