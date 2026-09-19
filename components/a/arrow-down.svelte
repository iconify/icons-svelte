<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m178_g6sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m178_g6sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-down" {...props}></Icon>
