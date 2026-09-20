<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5mxolbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="t5mxolbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-down-right" {...props}></Icon>
