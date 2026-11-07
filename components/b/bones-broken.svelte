<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fdmnrgb0f.css';
import '../../css/y/yt8oais7s.css';
import '../../css/s/si_mtzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fdmnrgb0f"/><path class="yt8oais7s"/><path class="si_mtzbvj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bones-broken" {...props}></Icon>
