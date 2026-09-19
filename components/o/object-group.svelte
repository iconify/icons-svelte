<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b_ji3pbxg.css';
import '../../css/h/ho8edbc3c.css';
import '../../css/s/sn-zpk_rn.css';
import '../../css/t/tf2gnt7zz.css';
import '../../css/a/arzdbwblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b_ji3pbxg"/><path class="ho8edbc3c"/><path clip-rule="evenodd" class="sn-zpk_rn"/><path class="tf2gnt7zz"/><path class="arzdbwblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:object-group" {...props}></Icon>
