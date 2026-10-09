<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o14cv2k9c.css';
import '../../css/e/eryruythf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o14cv2k9c"/><path class="eryruythf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:highlighter-20-bold" {...props}></Icon>
