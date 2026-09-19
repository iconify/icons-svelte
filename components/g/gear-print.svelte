<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lhv6-8bwl.css';
import '../../css/k/k73_c6bgm.css';
import '../../css/k/kp31dcc0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lhv6-8bwl"/><path class="k73_c6bgm"/><path class="kp31dcc0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:gear-print" {...props}></Icon>
