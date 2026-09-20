<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/osff_aczw.css';
import '../../css/o/ofuu2_ewz.css';
import '../../css/b/brad80bsu.css';
import '../../css/t/t_t8jppjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="osff_aczw"/><path class="ofuu2_ewz"/><path class="brad80bsu"/><path class="t_t8jppjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:currency-euro-dollar-exchange" {...props}></Icon>
