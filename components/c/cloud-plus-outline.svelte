<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie16_vbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie16_vbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-plus-outline" {...props}></Icon>
