<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqkgrobmp.css';
import '../../css/w/wh-3tcbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zqkgrobmp"/><path class="wh-3tcbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:java" {...props}></Icon>
