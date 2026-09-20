<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl96f8g_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl96f8g_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crop-outline" {...props}></Icon>
