<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yh2a82bhg.css';
import '../../css/d/dm44abbrd.css';
import '../../css/q/qgoe78bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh2a82bhg"/><path class="dm44abbrd"/><path class="qgoe78bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ranking2" {...props}></Icon>
