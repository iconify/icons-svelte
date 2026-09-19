<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5lee5t5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5lee5t5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin" {...props}></Icon>
