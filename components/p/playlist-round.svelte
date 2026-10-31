<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeucowb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeucowb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:playlist-round" {...props}></Icon>
