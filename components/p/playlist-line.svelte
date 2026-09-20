<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghpoz9b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghpoz9b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:playlist-line" {...props}></Icon>
