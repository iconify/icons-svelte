<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hq7-kg1-l.css';
import '../../css/v/vr39ulzpl.css';
import '../../css/d/d970nk8em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hq7-kg1-l"/><path class="vr39ulzpl"/><path class="d970nk8em"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-linear" {...props}></Icon>
