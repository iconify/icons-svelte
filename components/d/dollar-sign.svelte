<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk782fkpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk782fkpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dollar-sign" {...props}></Icon>
