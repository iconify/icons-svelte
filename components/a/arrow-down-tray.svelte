<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhoebv3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhoebv3dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-tray" {...props}></Icon>
