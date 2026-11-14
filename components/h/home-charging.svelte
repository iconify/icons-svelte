<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/w23k9ifmr.css';
import '../../css/z/zx2u6rbqg.css';
import '../../css/i/ivqiy5bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w23k9ifmr"/><path class="zx2u6rbqg"/><path class="ivqiy5bdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:home-charging" {...props}></Icon>
