<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec180qjdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":480};
const content = `<path class="ec180qjdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:directions-boat" {...props}></Icon>
