<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bmgc78bsz.css';
import '../../css/n/nasjo9_5v.css';
import '../../css/f/f0ly2e3dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bmgc78bsz"/><path class="nasjo9_5v"/><path class="f0ly2e3dy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:escalator-descend-person" {...props}></Icon>
