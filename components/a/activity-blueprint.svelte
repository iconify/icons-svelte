<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zwwoaxgmi.css';
import '../../css/l/l00otmbzz.css';
import '../../css/h/h1vixoucg.css';
import '../../css/c/c0l91kssj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zwwoaxgmi"/><path class="l00otmbzz wm-deco"/><path class="h1vixoucg"/><path class="c0l91kssj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:activity-blueprint" {...props}></Icon>
