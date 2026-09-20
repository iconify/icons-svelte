<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se7i_-b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se7i_-b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hdr-off" {...props}></Icon>
