<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk4txkbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk4txkbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-left" {...props}></Icon>
