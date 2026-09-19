<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzwgsdbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzwgsdbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:magnet-01" {...props}></Icon>
