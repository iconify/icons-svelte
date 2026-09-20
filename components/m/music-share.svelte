<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4t5zg9wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4t5zg9wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-share" {...props}></Icon>
