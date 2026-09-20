<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y0jvhibuk.css';
import '../../css/z/zrwz6z69g.css';
import '../../css/r/r51t0hbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y0jvhibuk"/><path clip-rule="evenodd" class="zrwz6z69g"/><path class="r51t0hbuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-history" {...props}></Icon>
