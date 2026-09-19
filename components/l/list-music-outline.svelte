<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu0mq3bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu0mq3bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:list-music-outline" {...props}></Icon>
