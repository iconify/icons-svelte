<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aerpob9ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aerpob9ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ccmp" {...props}></Icon>
