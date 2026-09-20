<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mxpiv0byi.css';
import '../../css/h/hdc10yrqn.css';
import '../../css/v/vwk_je8sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mxpiv0byi"/><path class="hdc10yrqn"/><path class="vwk_je8sw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:move-rectangle-left" {...props}></Icon>
