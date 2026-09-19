<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/edbboo-hy.css';
import '../../css/q/q4hhm4b9u.css';
import '../../css/m/mfc7nxp-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="edbboo-hy"/><path class="q4hhm4b9u"/><path class="mfc7nxp-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:book" {...props}></Icon>
