<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trlnbcbjf.css';
import '../../css/w/wie2-nbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trlnbcbjf"/><path class="wie2-nbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunasea" {...props}></Icon>
