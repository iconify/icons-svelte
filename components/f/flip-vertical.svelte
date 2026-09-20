<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2iq-ccn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2iq-ccn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flip-vertical" {...props}></Icon>
