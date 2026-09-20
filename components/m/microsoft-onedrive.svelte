<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfhd1vbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfhd1vbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-onedrive" {...props}></Icon>
