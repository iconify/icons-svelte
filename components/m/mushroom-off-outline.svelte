<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yft-ofbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yft-ofbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mushroom-off-outline" {...props}></Icon>
