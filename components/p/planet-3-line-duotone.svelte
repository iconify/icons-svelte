<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n75jjimak.css';
import '../../css/s/sxlf-3tyn.css';
import '../../css/g/gshkn9qqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n75jjimak"/><path class="sxlf-3tyn"/><path class="gshkn9qqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-3-line-duotone" {...props}></Icon>
