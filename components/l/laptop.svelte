<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/l0_ma0bfq.css';
import '../../css/v/vyu7oygnb.css';
import '../../css/s/sgrqeknne.css';
import '../../css/d/d-q6e3btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="l0_ma0bfq wm-shadow"/><path class="vyu7oygnb wm-shadow"/><path class="sgrqeknne"/><path class="d-q6e3btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:laptop" {...props}></Icon>
