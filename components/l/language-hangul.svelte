<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk2198b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vk2198b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hangul" {...props}></Icon>
