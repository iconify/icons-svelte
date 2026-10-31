<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/f_fz8wbma.css';
import '../../css/s/sz0wabcsi.css';
import '../../css/w/wbn73qbge.css';
import '../../css/u/uneyfrblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="f_fz8wbma wm-shadow"/><path class="sz0wabcsi wm-shadow"/><path class="wbn73qbge"/><path class="uneyfrblo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:book" {...props}></Icon>
