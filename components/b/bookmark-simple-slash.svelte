<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbt1e7ztl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wbt1e7ztl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-slash" {...props}></Icon>
