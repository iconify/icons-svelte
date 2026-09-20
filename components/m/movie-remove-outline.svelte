<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2b_yb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2b_yb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-remove-outline" {...props}></Icon>
