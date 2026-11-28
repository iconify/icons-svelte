<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbtm9ey6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xbtm9ey6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:copy-check-thin" {...props}></Icon>
