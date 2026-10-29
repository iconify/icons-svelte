<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vukr31bcm.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/b/b82dfnb_o.css';
import '../../css/j/jmo57ab0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vukr31bcm wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="b82dfnb_o wm-k"/><path class="jmo57ab0a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-x-blueprint" {...props}></Icon>
