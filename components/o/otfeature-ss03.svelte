<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gst0b_6kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gst0b_6kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ss03" {...props}></Icon>
