<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rc4qvxc7z.css';
import '../../css/l/lxvimfgoy.css';
import '../../css/k/k04p0xb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rc4qvxc7z"/><path class="lxvimfgoy"/><path class="k04p0xb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-line-duotone" {...props}></Icon>
