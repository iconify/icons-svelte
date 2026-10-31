<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rpmymt4-c.css';
import '../../css/n/n-f0l1bjt.css';
import '../../css/r/r35wb3bpv.css';
import '../../css/n/nw1asb53l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rpmymt4-c wm-shadow"/><path class="n-f0l1bjt wm-shadow"/><path class="r35wb3bpv"/><path class="nw1asb53l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:pilcrow" {...props}></Icon>
