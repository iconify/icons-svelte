<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lmr25hber.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/t/twrukyb-k.css';
import '../../css/o/od9eo774w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lmr25hber wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="twrukyb-k"/><path class="od9eo774w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-circle-blueprint" {...props}></Icon>
