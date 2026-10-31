<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pxn7uxd0b.css';
import '../../css/n/n0viuuyml.css';
import '../../css/m/mfrjwluok.css';
import '../../css/s/s0okuubdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pxn7uxd0b wm-shadow"/><path class="n0viuuyml wm-shadow"/><path class="mfrjwluok"/><path class="s0okuubdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:bot" {...props}></Icon>
