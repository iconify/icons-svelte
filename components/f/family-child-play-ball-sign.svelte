<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qelrpmbxt.css';
import '../../css/q/q9a1p2t7g.css';
import '../../css/c/ca6vo_0ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qelrpmbxt"/><path class="q9a1p2t7g"/><path class="ca6vo_0ub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:family-child-play-ball-sign" {...props}></Icon>
