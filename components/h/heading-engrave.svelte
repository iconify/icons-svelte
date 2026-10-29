<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hhllkrd_f.css';
import '../../css/j/jn3admwwv.css';
import '../../css/e/ex1wvfboz.css';
import '../../css/f/fed5n4npn.css';
import '../../css/v/vslz5yb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hhllkrd_f wm-k"/><path class="jn3admwwv wm-a"/><path class="ex1wvfboz wm-shadow"/><path class="fed5n4npn wm-k"/><path class="vslz5yb3q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heading-engrave" {...props}></Icon>
