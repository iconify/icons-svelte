<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vl1yu0n4m.css';
import '../../css/e/eph851bhm.css';
import '../../css/p/ptmeui_8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vl1yu0n4m"/><path class="eph851bhm"/><path class="ptmeui_8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:exclude" {...props}></Icon>
