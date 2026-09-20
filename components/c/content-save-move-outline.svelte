<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoac4dbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoac4dbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-move-outline" {...props}></Icon>
