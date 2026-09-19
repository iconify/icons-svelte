<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o_e9bzw-o.css';
import '../../css/o/oszh--blj.css';
import '../../css/h/hrr5vnrqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_e9bzw-o"/><path class="oszh--blj"/><path class="hrr5vnrqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:home-10" {...props}></Icon>
