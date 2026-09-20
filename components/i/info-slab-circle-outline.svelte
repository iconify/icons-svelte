<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuptu5b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuptu5b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-slab-circle-outline" {...props}></Icon>
