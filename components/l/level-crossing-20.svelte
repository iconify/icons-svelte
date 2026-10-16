<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peoarebot.css';
import '../../css/n/n0urq0a3z.css';
import '../../css/f/fch6rrymb.css';
import '../../css/o/ox6y2ub3r.css';
import '../../css/b/bas8edbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="peoarebot"/><path class="n0urq0a3z"/><path class="fch6rrymb"/><path class="ox6y2ub3r"/><path class="bas8edbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:level-crossing-20" {...props}></Icon>
