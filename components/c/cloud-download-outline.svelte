<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbt3a1b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbt3a1b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-download-outline" {...props}></Icon>
