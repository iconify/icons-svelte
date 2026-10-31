<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rawx_4jhd.css';
import '../../css/t/tu0nkzb6s.css';
import '../../css/p/py3r1nbdl.css';
import '../../css/c/ct1pmlklf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rawx_4jhd wm-shadow"/><path class="tu0nkzb6s wm-shadow"/><path class="py3r1nbdl"/><path class="ct1pmlklf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:crosshair" {...props}></Icon>
