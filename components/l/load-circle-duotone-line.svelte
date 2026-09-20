<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0crath5f.css';
import '../../css/a/aqpre-vwq.css';
import '../../css/r/rnbvk1bmo.css';
import '../../css/a/a1ya6bbne.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGsLIN5oiv"><g class="ft5dv1b6b"><circle transform="matrix(0 -1 -1 0 17 20)" class="o0crath5f"/><circle transform="matrix(0 -1 -1 0 17 20)" class="aqpre-vwq"/><path class="rnbvk1bmo"/><path class="a1ya6bbne"/></g></mask></defs><path mask="url(#SVGsLIN5oiv)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:load-circle-duotone-line" {...props}></Icon>
