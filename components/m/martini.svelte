<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qg4pciyrw.css';
import '../../css/r/rt0e5mb6z.css';
import '../../css/g/ggrjl0bje.css';
import '../../css/s/sxmtimb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="qg4pciyrw wm-shadow"/><path class="rt0e5mb6z"/><path class="ggrjl0bje"/><path class="sxmtimb3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:martini" {...props}></Icon>
