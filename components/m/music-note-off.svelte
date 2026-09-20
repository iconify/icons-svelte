<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4mq8zejn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4mq8zejn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-off" {...props}></Icon>
