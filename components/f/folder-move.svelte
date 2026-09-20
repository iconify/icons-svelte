<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-6p2220y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-6p2220y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-move" {...props}></Icon>
