<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2lrza4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2lrza4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-full" {...props}></Icon>
