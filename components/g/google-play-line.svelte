<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sui2wjb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sui2wjb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:google-play-line" {...props}></Icon>
