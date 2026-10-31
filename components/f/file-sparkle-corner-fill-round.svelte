<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmjz6fb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmjz6fb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-sparkle-corner-fill-round" {...props}></Icon>
