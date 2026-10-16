<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcea63bav.css';
import '../../css/r/rtjb2ejcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fcea63bav"/><path class="rtjb2ejcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phase-shifter-20-bold" {...props}></Icon>
