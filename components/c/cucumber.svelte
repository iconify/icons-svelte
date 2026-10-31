<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lucauldwf.css';
import '../../css/y/y9kjc6bfx.css';
import '../../css/a/a2ai9tcjf.css';
import '../../css/l/lgrei8-mr.css';
import '../../css/e/ews49cctm.css';
import '../../css/l/l-fs14mhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="lucauldwf"/><path class="y9kjc6bfx"/><path class="a2ai9tcjf"/><path class="lgrei8-mr"/><path class="ews49cctm"/><path class="l-fs14mhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:cucumber" {...props}></Icon>
