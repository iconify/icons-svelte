<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsbddlk4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fsbddlk4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:desktop-computer-filled" {...props}></Icon>
