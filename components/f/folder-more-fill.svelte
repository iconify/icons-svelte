<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlk0_mb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlk0_mb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-more-fill" {...props}></Icon>
