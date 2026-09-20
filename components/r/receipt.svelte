<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mh56y2inu.css';
import '../../css/a/a-1uicclk.css';
import '../../css/h/hf53x_ydx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mh56y2inu"/><path class="a-1uicclk"/><path class="hf53x_ydx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:receipt" {...props}></Icon>
