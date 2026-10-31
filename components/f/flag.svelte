<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sv4cljb-z.css';
import '../../css/e/en-mohuvb.css';
import '../../css/d/dgpnbnawx.css';
import '../../css/n/ngkbrebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sv4cljb-z wm-shadow"/><path class="en-mohuvb wm-shadow"/><path class="dgpnbnawx"/><path class="ngkbrebze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:flag" {...props}></Icon>
