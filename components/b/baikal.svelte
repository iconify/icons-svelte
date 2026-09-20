<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ehv2bir.css';
import '../../css/r/r9ydwtb-m.css';
import '../../css/y/yizda5rca.css';
import '../../css/d/d27-lzbxa.css';
import '../../css/y/y83axdbzc.css';
import '../../css/q/qgo9spqhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_ehv2bir"/><path class="r9ydwtb-m"/><circle class="yizda5rca"/><path class="d27-lzbxa"/><path class="y83axdbzc"/><path class="qgo9spqhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baikal" {...props}></Icon>
