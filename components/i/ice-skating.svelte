<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mt6-5jbev.css';
import '../../css/w/wyv4swb6z.css';
import '../../css/b/b0le1zb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mt6-5jbev"/><path class="wyv4swb6z"/><path class="b0le1zb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ice-skating" {...props}></Icon>
