<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/w85widokh.css';
import '../../css/t/t8jn3g9nm.css';
import '../../css/k/kkcp04bje.css';
import '../../css/i/iwnz01bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="w85widokh wm-shadow"/><path class="t8jn3g9nm wm-shadow"/><path class="kkcp04bje"/><path class="iwnz01bfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:plus" {...props}></Icon>
