<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xk2i9cb9l.css';
import '../../css/f/f5h9bqb3b.css';
import '../../css/s/sa73k2b9u.css';
import '../../css/d/d6bk21--u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xk2i9cb9l"/><path class="f5h9bqb3b wm-a"/><path class="sa73k2b9u wm-k"/><path class="d6bk21--u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-pause-sketch" {...props}></Icon>
