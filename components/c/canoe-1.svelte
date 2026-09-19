<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dgv3dpb-u.css';
import '../../css/o/o6l7tkb7s.css';
import '../../css/u/um8386b8f.css';
import '../../css/l/lv8_-5sui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dgv3dpb-u"/><path class="o6l7tkb7s"/><path class="um8386b8f"/><path class="lv8_-5sui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:canoe-1" {...props}></Icon>
