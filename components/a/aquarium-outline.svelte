<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-x6lpj1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-x6lpj1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:aquarium-outline" {...props}></Icon>
