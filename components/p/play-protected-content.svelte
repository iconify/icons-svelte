<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1hdy1ggy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1hdy1ggy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-protected-content" {...props}></Icon>
