<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsza4_yqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsza4_yqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-2-fill" {...props}></Icon>
