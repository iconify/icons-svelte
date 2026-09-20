<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so4ohuxyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="so4ohuxyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-left" {...props}></Icon>
