<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq3o2etsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq3o2etsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-heart" {...props}></Icon>
