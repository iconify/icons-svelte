<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tlpz02qyr.css';
import '../../css/b/bp1dflhdl.css';
import '../../css/a/asqd14bur.css';
import '../../css/w/w7adcibse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="tlpz02qyr"/><path class="bp1dflhdl"/><path class="asqd14bur"/><path class="w7adcibse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:globe" {...props}></Icon>
