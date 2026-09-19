<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgr_vgb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgr_vgb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:long-legged-spider" {...props}></Icon>
