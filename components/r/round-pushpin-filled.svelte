<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2osepb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n2osepb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:round-pushpin-filled" {...props}></Icon>
