<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wr-t-5oaa.css';
import '../../css/q/qcw4u49ik.css';
import '../../css/n/ngtd4hbhd.css';
import '../../css/f/f24suco6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr-t-5oaa"/><path class="qcw4u49ik"/><path class="ngtd4hbhd"/><path class="f24suco6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:metro" {...props}></Icon>
