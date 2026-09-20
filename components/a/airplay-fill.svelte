<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwoa4qbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwoa4qbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airplay-fill" {...props}></Icon>
