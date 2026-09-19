<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkl5tz40n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vkl5tz40n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bread" {...props}></Icon>
