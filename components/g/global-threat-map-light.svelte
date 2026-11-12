<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmc55qbpv.css';
import '../../css/g/g5l3qyt-f.css';
import '../../css/w/wlqkezb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmc55qbpv"/><circle class="g5l3qyt-f"/><circle class="wlqkezb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:global-threat-map-light" {...props}></Icon>
