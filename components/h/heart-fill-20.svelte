<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx63x44ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rx63x44ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heart-fill-20" {...props}></Icon>
