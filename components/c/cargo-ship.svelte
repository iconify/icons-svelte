<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tpkegzb2d.css';
import '../../css/q/qwj7qphyr.css';
import '../../css/u/uefrb7b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpkegzb2d"/><path class="qwj7qphyr"/><path class="uefrb7b_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cargo-ship" {...props}></Icon>
