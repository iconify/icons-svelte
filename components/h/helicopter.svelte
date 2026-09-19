<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h4bt2rbgf.css';
import '../../css/g/g3fsjcc0x.css';
import '../../css/b/bk22yqxkn.css';
import '../../css/p/p98550h_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h4bt2rbgf"/><path class="g3fsjcc0x"/><path clip-rule="evenodd" class="bk22yqxkn"/><path clip-rule="evenodd" class="p98550h_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:helicopter" {...props}></Icon>
