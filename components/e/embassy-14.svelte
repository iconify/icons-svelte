<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2_7ilyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cv2_7ilyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:embassy-14" {...props}></Icon>
