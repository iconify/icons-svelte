<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykcgx-bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykcgx-bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flowerpot-fill" {...props}></Icon>
