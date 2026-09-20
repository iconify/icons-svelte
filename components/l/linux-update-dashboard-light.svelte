<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg35-r2sk.css';
import '../../css/n/n_--nwb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg35-r2sk"/><path class="n_--nwb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linux-update-dashboard-light" {...props}></Icon>
