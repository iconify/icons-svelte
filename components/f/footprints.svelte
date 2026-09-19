<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs9vf3byp.css';
import '../../css/u/um8_dl0cx.css';
import '../../css/w/w8z8pgbyr.css';
import '../../css/q/q3rujdbek.css';
import '../../css/b/b376ql6hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="vs9vf3byp"><path class="um8_dl0cx"/><path class="w8z8pgbyr"/><path class="q3rujdbek"/><path class="b376ql6hm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:footprints" {...props}></Icon>
