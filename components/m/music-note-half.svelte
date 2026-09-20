<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4rittb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4rittb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-half" {...props}></Icon>
