<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xke_bo0dv.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/o/osg7x0btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xke_bo0dv"/><path class="g4vvtk_cw"/><path class="osg7x0btl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:earth-duotone" {...props}></Icon>
