<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uy0_c856w.css';
import '../../css/u/u96oi128d.css';
import '../../css/p/pyvr7j5_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uy0_c856w"/><path class="u96oi128d"/><path class="pyvr7j5_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-browser" {...props}></Icon>
