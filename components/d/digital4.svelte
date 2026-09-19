<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k749s-bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k749s-bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital4" {...props}></Icon>
