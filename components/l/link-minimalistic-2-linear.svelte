<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hjuar3b7p.css';
import '../../css/d/dtoolxbmj.css';
import '../../css/u/urpswfa4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hjuar3b7p"/><path class="dtoolxbmj"/><path class="urpswfa4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-2-linear" {...props}></Icon>
