<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-t9hbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-t9hbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dock-left" {...props}></Icon>
