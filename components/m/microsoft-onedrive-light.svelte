<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/accicg2ns.css';
import '../../css/w/wicut5btr.css';
import '../../css/l/le8lm-bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="accicg2ns"/><path class="wicut5btr"/><path class="le8lm-bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-light" {...props}></Icon>
