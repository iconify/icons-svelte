<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obf8cbbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obf8cbbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playlist-play" {...props}></Icon>
