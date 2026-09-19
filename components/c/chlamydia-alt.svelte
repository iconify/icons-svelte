<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gu71owqar.css';
import '../../css/i/isras2boi.css';
import '../../css/r/r8sdp5bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="gu71owqar"/><path clip-rule="evenodd" class="isras2boi"/><path class="r8sdp5bdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chlamydia-alt" {...props}></Icon>
