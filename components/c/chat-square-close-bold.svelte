<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsbxb1bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsbxb1bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-close-bold" {...props}></Icon>
