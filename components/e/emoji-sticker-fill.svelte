<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ryo4pfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ryo4pfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emoji-sticker-fill" {...props}></Icon>
