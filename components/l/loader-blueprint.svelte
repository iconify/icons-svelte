<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bjqil1l7x.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/q/qa-0fibzt.css';
import '../../css/e/ey65q7bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bjqil1l7x wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="qa-0fibzt wm-k"/><path class="ey65q7bnk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-blueprint" {...props}></Icon>
