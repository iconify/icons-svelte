<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sho0vcbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sho0vcbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-vpn" {...props}></Icon>
