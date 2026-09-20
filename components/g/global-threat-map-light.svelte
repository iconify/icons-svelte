<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmc55qbpv.css';
import '../../css/p/p48_jkbmd.css';
import '../../css/g/gom_ccb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmc55qbpv"/><circle class="p48_jkbmd"/><circle class="gom_ccb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:global-threat-map-light" {...props}></Icon>
