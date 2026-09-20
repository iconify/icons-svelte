<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie1_ubcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie1_ubcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-key-network-outline" {...props}></Icon>
