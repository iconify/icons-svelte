<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6805ccbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6805ccbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-video-outline" {...props}></Icon>
