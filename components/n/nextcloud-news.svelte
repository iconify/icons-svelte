<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1v2sdoj.css';
import '../../css/w/wufxdip_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="wufxdip_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-news" {...props}></Icon>
