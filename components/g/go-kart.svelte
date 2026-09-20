<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8-2mtl-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-2mtl-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:go-kart" {...props}></Icon>
