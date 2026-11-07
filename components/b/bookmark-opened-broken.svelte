<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f5hn4upfu.css';
import '../../css/n/nkncs4b1r.css';
import '../../css/o/ollsq1blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f5hn4upfu"/><path class="nkncs4b1r"/><path class="ollsq1blz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-opened-broken" {...props}></Icon>
