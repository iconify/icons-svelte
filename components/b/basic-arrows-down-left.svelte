<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv13xuqdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zv13xuqdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-down-left" {...props}></Icon>
