<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/y/yoskqcbdm.css';
import '../../css/j/jt6io-b3f.css';
import '../../css/i/i_bd-bc3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><path class="yoskqcbdm"/><circle class="jt6io-b3f"/><circle class="i_bd-bc3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:meh" {...props}></Icon>
