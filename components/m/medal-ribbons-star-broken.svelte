<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pfjefkbxt.css';
import '../../css/n/nw92swb-t.css';
import '../../css/u/upow0ezwy.css';
import '../../css/h/hsdae9b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pfjefkbxt"/><path class="nw92swb-t"/><path class="upow0ezwy"/><path class="hsdae9b6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-broken" {...props}></Icon>
