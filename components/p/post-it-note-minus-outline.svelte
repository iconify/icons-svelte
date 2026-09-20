<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq5z0w1nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq5z0w1nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note-minus-outline" {...props}></Icon>
