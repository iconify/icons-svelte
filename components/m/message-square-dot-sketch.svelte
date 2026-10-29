<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/blrw_ccba.css';
import '../../css/v/vrq2xh5oj.css';
import '../../css/z/zf8t9262c.css';
import '../../css/h/h0tlrdy7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="blrw_ccba"/><path class="vrq2xh5oj wm-k"/><path class="wm-k zf8t9262c"/><path class="h0tlrdy7i wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-dot-sketch" {...props}></Icon>
