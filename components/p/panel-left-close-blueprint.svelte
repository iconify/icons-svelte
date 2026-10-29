<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hv8fxdvrh.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/f/fz9wbhbib.css';
import '../../css/p/phr4i2wxy.css';
import '../../css/j/j-4i0l2fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hv8fxdvrh wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="fz9wbhbib wm-k"/><path class="phr4i2wxy wm-a"/><path class="j-4i0l2fr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-left-close-blueprint" {...props}></Icon>
