<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np-5m-b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np-5m-b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:house-wifi-solid" {...props}></Icon>
