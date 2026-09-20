<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv7m9pbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv7m9pbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forum-delete" {...props}></Icon>
