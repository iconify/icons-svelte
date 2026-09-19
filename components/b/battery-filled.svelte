<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk2u_7bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vk2u_7bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:battery-filled" {...props}></Icon>
