<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sb9vkzbhd.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/j/jffir3tnu.css';
import '../../css/q/q1ap8wbyv.css';
import '../../css/q/qz5pats7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sb9vkzbhd wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="jffir3tnu wm-k"/><path class="q1ap8wbyv wm-a"/><path class="qz5pats7o wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:love-letter-blueprint" {...props}></Icon>
