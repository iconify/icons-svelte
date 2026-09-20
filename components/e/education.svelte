<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mpr19ccyx.css';
import '../../css/o/ox2f6xb_t.css';
import '../../css/c/cjd1zynuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mpr19ccyx"/><path class="ox2f6xb_t"/><path class="cjd1zynuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:education" {...props}></Icon>
