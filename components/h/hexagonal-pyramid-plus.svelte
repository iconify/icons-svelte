<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk5app3bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk5app3bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagonal-pyramid-plus" {...props}></Icon>
