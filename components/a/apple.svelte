<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fvr3jsble.css';
import '../../css/g/gbq5i-bmx.css';
import '../../css/s/sh51cwb0x.css';
import '../../css/p/pdike1b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fvr3jsble wm-shadow"/><path class="gbq5i-bmx wm-shadow"/><path class="sh51cwb0x"/><path class="pdike1b1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:apple" {...props}></Icon>
