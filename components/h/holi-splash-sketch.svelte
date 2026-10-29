<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lbj85ed8c.css';
import '../../css/z/zzhn1q2in.css';
import '../../css/g/g3kzkz79z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lbj85ed8c wm-k"/><path class="wm-a zzhn1q2in"/><path class="g3kzkz79z wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:holi-splash-sketch" {...props}></Icon>
