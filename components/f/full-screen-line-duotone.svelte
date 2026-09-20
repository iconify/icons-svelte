<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i8utatbio.css';
import '../../css/x/x-1lf64uh.css';
import '../../css/u/un-u7xpwr.css';
import '../../css/r/ros5bvrws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i8utatbio"/><path class="x-1lf64uh"/><path class="un-u7xpwr"/><path class="ros5bvrws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-line-duotone" {...props}></Icon>
