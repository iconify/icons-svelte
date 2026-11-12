<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/accicg2ns.css';
import '../../css/l/ldtpmn0ux.css';
import '../../css/l/l52qpcb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="accicg2ns"/><path class="ldtpmn0ux"/><path class="l52qpcb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-light" {...props}></Icon>
