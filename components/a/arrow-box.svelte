<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxgvstbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":448};
const content = `<path class="pxgvstbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:arrow-box" {...props}></Icon>
