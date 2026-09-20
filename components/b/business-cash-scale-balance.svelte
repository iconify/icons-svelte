<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/awghp3pyj.css';
import '../../css/l/l9s63tb1w.css';
import '../../css/d/dr_3fr28m.css';
import '../../css/r/r6hn8gbbw.css';
import '../../css/j/j4-bubc4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="awghp3pyj"/><path class="l9s63tb1w"/><path class="dr_3fr28m"/><path class="r6hn8gbbw"/><path class="j4-bubc4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-cash-scale-balance" {...props}></Icon>
