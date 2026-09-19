<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fzvp0ibac.css';
import '../../css/q/qpzakybpx.css';
import '../../css/p/p01jvacul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fzvp0ibac"/><path class="qpzakybpx"/><path class="p01jvacul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chrysler" {...props}></Icon>
