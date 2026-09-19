<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s9fynmwrw.css';
import '../../css/z/ztw77h30a.css';
import '../../css/w/ws3epobig.css';
import '../../css/x/xkxxr0bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s9fynmwrw"/><path class="ztw77h30a"/><path class="ws3epobig"/><path class="xkxxr0bfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:root-3rd-bracket" {...props}></Icon>
