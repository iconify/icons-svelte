<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yrn1x2sgp.css';
import '../../css/y/yys4-bbwv.css';
import '../../css/v/vrwwxccjf.css';
import '../../css/f/f3j45ub3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yrn1x2sgp"/><path class="yys4-bbwv"/><path class="vrwwxccjf"/><path class="f3j45ub3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:presentation-screen" {...props}></Icon>
