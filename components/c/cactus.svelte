<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b4_l1obsd.css';
import '../../css/d/dr2ub2b3c.css';
import '../../css/w/ww6dn4vxg.css';
import '../../css/w/wb62jpb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b4_l1obsd wm-shadow"/><path class="dr2ub2b3c wm-shadow"/><path class="ww6dn4vxg"/><path class="wb62jpb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:cactus" {...props}></Icon>
