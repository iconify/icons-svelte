<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_g7rv5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf_g7rv5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-music-fill" {...props}></Icon>
