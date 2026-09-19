<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r89124h4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r89124h4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:microphone-slash" {...props}></Icon>
