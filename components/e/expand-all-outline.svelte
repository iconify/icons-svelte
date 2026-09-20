<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndi6ggb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndi6ggb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:expand-all-outline" {...props}></Icon>
