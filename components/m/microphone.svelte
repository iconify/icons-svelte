<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn4ka_0ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="yn4ka_0ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microphone" {...props}></Icon>
