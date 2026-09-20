<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypfwpeqha.css';
import '../../css/t/tqahksbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypfwpeqha"/><path class="tqahksbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openwrt" {...props}></Icon>
