<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh4l9jb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh4l9jb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevron-up" {...props}></Icon>
