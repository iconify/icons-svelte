<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a_d063p8k.css';
import '../../css/n/nm8on7bej.css';
import '../../css/l/lxxaunp0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="a_d063p8k"/><path class="nm8on7bej"/><path class="lxxaunp0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:helicopter-duo" {...props}></Icon>
