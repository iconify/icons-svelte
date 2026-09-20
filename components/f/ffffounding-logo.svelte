<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2vtcs3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2vtcs3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ffffounding-logo" {...props}></Icon>
