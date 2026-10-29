<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/h2gyn-b9k.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/b/b82dfnb_o.css';
import '../../css/i/i9rgmobgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="h2gyn-b9k wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="b82dfnb_o wm-k"/><path class="i9rgmobgb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-alert-blueprint" {...props}></Icon>
