<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwv3g5b-i.css';
import '../../css/x/xftpn6bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwv3g5b-i"/><path class="xftpn6bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bigcapital" {...props}></Icon>
