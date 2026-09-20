<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkm48071l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkm48071l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-music" {...props}></Icon>
