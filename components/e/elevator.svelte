<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h8qf3b_7u.css';
import '../../css/l/lyaqavbsk.css';
import '../../css/t/tm8mw0bav.css';
import '../../css/q/qh2kqpq0h.css';
import '../../css/j/jkt38pbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="h8qf3b_7u"/><circle class="lyaqavbsk"/><path class="tm8mw0bav"/><circle class="qh2kqpq0h"/><path class="jkt38pbrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:elevator" {...props}></Icon>
