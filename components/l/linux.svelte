<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ilbc9tc8n.css';
import '../../css/u/uusfhccwf.css';
import '../../css/r/r4a85nb6r.css';
import '../../css/h/hfqd4dtjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="ilbc9tc8n"/><rect class="uusfhccwf"/><path class="r4a85nb6r"/><path class="hfqd4dtjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:linux" {...props}></Icon>
