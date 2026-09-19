<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7zrlbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="hu7zrlbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-paused" {...props}></Icon>
