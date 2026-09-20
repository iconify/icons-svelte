<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbxsfdaxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbxsfdaxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:aquarium" {...props}></Icon>
