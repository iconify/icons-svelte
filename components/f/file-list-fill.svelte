<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdzu280gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdzu280gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-list-fill" {...props}></Icon>
