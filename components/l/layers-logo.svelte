<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o-v3vrb3z.css';
import '../../css/m/mhtdy_mav.css';
import '../../css/y/yb2lqrucn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-v3vrb3z"/><path class="mhtdy_mav"/><path class="yb2lqrucn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layers-logo" {...props}></Icon>
