<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/urdc96bbo.css';
import '../../css/y/yrwyo22db.css';
import '../../css/a/awbyonb8h.css';
import '../../css/r/r_vybwbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="urdc96bbo"/><path class="yrwyo22db"/><path class="awbyonb8h"/><path class="r_vybwbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:presentation-projector-1" {...props}></Icon>
