<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy6vjcb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy6vjcb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-outline" {...props}></Icon>
