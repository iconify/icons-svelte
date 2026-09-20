<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2wa8biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2wa8biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hivemq" {...props}></Icon>
