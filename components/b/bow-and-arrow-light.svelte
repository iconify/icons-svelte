<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycfpyuufe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ycfpyuufe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bow-and-arrow-light" {...props}></Icon>
