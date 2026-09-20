<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rl-fbwnpe.css';
import '../../css/q/qhz8-fyzm.css';
import '../../css/o/obibidbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rl-fbwnpe"/><path class="qhz8-fyzm"/><path class="obibidbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:film-roll-1-flat" {...props}></Icon>
