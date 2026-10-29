<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yq4w0ibij.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/x/xtdeyac8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yq4w0ibij"/><path class="o7-ag87sb wm-deco"/><path class="xtdeyac8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-blueprint" {...props}></Icon>
