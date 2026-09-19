<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgw_3z_ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgw_3z_ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:baseball-glove" {...props}></Icon>
