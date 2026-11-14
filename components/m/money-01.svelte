<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/ao328ib6p.css';
import '../../css/d/dgn65lb1h.css';
import '../../css/t/tl_x59b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ao328ib6p"/><path class="dgn65lb1h"/><path class="tl_x59b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-01" {...props}></Icon>
