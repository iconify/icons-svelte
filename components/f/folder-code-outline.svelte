<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt07y0bxu.css';
import '../../css/y/y1r440bhs.css';
import '../../css/m/mxpx_sbmx.css';
import '../../css/p/pzmtr-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt07y0bxu"/><path class="y1r440bhs"/><path class="mxpx_sbmx"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-code-outline" {...props}></Icon>
