<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z1u9cxbgl.css';
import '../../css/x/xh2lgbbiy.css';
import '../../css/z/zsv03u5kq.css';
import '../../css/n/n7d_avo5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z1u9cxbgl"/><path class="xh2lgbbiy"/><path class="zsv03u5kq"/><path class="n7d_avo5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cucumber" {...props}></Icon>
