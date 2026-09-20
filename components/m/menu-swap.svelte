<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3_pa8bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3_pa8bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-swap" {...props}></Icon>
