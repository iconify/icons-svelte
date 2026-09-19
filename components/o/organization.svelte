<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bno8x-bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bno8x-bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:organization" {...props}></Icon>
