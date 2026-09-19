<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hrt15xihn.css';
import '../../css/d/dfb6i3blf.css';
import '../../css/s/shnvllc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hrt15xihn"/><path class="dfb6i3blf"/><path class="shnvllc_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:drag-right-03" {...props}></Icon>
