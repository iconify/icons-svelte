<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/whwpro6ey.css';
import '../../css/f/fyssiwbsm.css';
import '../../css/o/olzrecbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="whwpro6ey"/><path class="fyssiwbsm"/><path class="olzrecbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:key-square-duotone" {...props}></Icon>
