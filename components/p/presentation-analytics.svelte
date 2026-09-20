<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sxobkfzzi.css';
import '../../css/k/k-wrf3ppr.css';
import '../../css/g/gbagby-8i.css';
import '../../css/b/bnj4hpocw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sxobkfzzi"/><path class="k-wrf3ppr"/><path class="gbagby-8i"/><path class="bnj4hpocw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:presentation-analytics" {...props}></Icon>
