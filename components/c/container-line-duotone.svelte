<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jeopszbig.css';
import '../../css/x/xtp4t3bcd.css';
import '../../css/f/f6nuepbyg.css';
import '../../css/p/pnozs4hcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jeopszbig"/><path class="xtp4t3bcd"/><path class="f6nuepbyg"/><path class="pnozs4hcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:container-line-duotone" {...props}></Icon>
