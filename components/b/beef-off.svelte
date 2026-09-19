<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r-qd7_b_c.css';
import '../../css/f/f9iub6b_k.css';
import '../../css/h/hushrnb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-qd7_b_c"/><path class="f9iub6b_k"/><path class="hushrnb6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:beef-off" {...props}></Icon>
