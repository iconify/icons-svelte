<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/t0e5e1bzb.css';
import '../../css/k/k3vkrebco.css';
import '../../css/y/y5d_3bbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0e5e1bzb"/><path class="k3vkrebco"/><path class="y5d_3bbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:home-11" {...props}></Icon>
