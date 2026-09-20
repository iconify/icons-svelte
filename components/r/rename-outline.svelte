<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwgzm4b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwgzm4b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rename-outline" {...props}></Icon>
