<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qsplo5bng.css';
import '../../css/z/zj7p6wbad.css';
import '../../css/w/wr1w-sbdc.css';
import '../../css/a/awxnmibuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="qsplo5bng"/><path class="zj7p6wbad"/><ellipse class="wr1w-sbdc"/><ellipse class="awxnmibuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:faceu" {...props}></Icon>
