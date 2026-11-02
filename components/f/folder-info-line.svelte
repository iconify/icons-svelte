<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m29_9ds_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m29_9ds_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-info-line" {...props}></Icon>
