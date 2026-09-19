<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycekqlkyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ycekqlkyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital3" {...props}></Icon>
