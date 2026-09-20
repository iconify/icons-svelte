<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_u_3eq7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_u_3eq7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:resize-bottom-right" {...props}></Icon>
