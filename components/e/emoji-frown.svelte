<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qh4l7r3-i.css';
import '../../css/t/tk3k4fb_w.css';
import '../../css/i/i73u7ccvd.css';
import '../../css/h/hh34r8rul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="qh4l7r3-i"/><circle class="tk3k4fb_w"/><circle class="i73u7ccvd"/><path class="hh34r8rul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:emoji-frown" {...props}></Icon>
