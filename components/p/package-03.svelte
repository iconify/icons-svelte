<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g5uq_vbhz.css';
import '../../css/z/ztkbymavw.css';
import '../../css/e/e5s_c9bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5uq_vbhz"/><path class="ztkbymavw"/><path class="e5s_c9bsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-03" {...props}></Icon>
