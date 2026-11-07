<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3vb0177b.css';
import '../../css/n/nvazcab2q.css';
import '../../css/l/lh00_hb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3vb0177b"/><path class="nvazcab2q"/><path class="lh00_hb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-bold-duotone" {...props}></Icon>
