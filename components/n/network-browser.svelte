<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dg5ykdbtd.css';
import '../../css/u/uj6ju-bjn.css';
import '../../css/j/jz1nelbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dg5ykdbtd"/><path class="uj6ju-bjn"/><path class="jz1nelbbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-browser" {...props}></Icon>
