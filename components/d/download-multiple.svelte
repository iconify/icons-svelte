<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ids20-b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ids20-b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-multiple" {...props}></Icon>
