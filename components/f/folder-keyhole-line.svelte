<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdbshfbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdbshfbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-keyhole-line" {...props}></Icon>
