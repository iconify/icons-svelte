<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nwlcuwbts.css';
import '../../css/q/qa-1pv6bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nwlcuwbts"/><circle class="qa-1pv6bo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:print" {...props}></Icon>
