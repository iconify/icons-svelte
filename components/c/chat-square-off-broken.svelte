<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/re4elkb7b.css';
import '../../css/z/zg90ki5is.css';
import '../../css/r/rqx2gjabx.css';
import '../../css/r/rjy1xybnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="re4elkb7b"/><path class="zg90ki5is"/><path class="rqx2gjabx"/><path class="rjy1xybnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-off-broken" {...props}></Icon>
