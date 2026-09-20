<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5qi60--x.css';
import '../../css/z/zqip_ybwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qi60--x"/><path class="zqip_ybwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:chat" {...props}></Icon>
