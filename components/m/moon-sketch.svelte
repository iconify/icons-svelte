<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q471_irwr.css';
import '../../css/n/nhv4ufbsv.css';
import '../../css/a/a762wedry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q471_irwr"/><path class="nhv4ufbsv"/><path class="a762wedry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon-sketch" {...props}></Icon>
