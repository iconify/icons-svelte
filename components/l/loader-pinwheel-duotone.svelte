<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r-z4_hb7l.css';
import '../../css/o/oxwyg8bmt.css';
import '../../css/r/r0sby3b4c.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/o/osanvnb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r-z4_hb7l"/><path class="oxwyg8bmt"/><path class="r0sby3b4c"/><path class="g4vvtk_cw"/><path class="osanvnb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:loader-pinwheel-duotone" {...props}></Icon>
