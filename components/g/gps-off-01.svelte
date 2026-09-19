<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jpl_0rwdp.css';
import '../../css/a/ar26nubux.css';
import '../../css/w/wc7iz8b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jpl_0rwdp"/><path class="ar26nubux"/><path class="wc7iz8b7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gps-off-01" {...props}></Icon>
