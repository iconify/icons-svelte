<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dzws6zn0x.css';
import '../../css/c/c55ag9btm.css';
import '../../css/r/roh-o2f0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dzws6zn0x"/><circle class="c55ag9btm"/><path class="roh-o2f0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-2-broken" {...props}></Icon>
