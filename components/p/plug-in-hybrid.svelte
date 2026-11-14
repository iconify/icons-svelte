<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v5o37lmcf.css';
import '../../css/f/fl825d_-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v5o37lmcf"/><path class="fl825d_-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:plug-in-hybrid" {...props}></Icon>
