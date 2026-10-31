<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tjr92xbfv.css';
import '../../css/y/yd1resboj.css';
import '../../css/e/e66ihdb7b.css';
import '../../css/s/s81899b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tjr92xbfv wm-shadow"/><path class="wm-shadow yd1resboj"/><path class="e66ihdb7b"/><path class="s81899b3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:plane" {...props}></Icon>
