<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgig-me-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mgig-me-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:microphone-lines-slash" {...props}></Icon>
