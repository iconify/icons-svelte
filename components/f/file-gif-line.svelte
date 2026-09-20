<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0dksb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy0dksb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-gif-line" {...props}></Icon>
