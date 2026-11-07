<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hs6rbmbln.css';
import '../../css/w/w722mfbgk.css';
import '../../css/m/mayyj1h2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hs6rbmbln"/><path class="w722mfbgk"/><path class="mayyj1h2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-broken" {...props}></Icon>
