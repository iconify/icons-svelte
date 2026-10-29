<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n8yc7ccpm.css';
import '../../css/i/i9rgmobgb.css';
import '../../css/b/b82dfnb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n8yc7ccpm"/><path class="i9rgmobgb wm-a"/><path class="b82dfnb_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-alert-duo" {...props}></Icon>
