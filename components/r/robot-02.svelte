<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/m8-2vl3ci.css';
import '../../css/k/kh86v1ben.css';
import '../../css/t/trc6hlbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8-2vl3ci"/><circle class="kh86v1ben"/><path class="trc6hlbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:robot-02" {...props}></Icon>
