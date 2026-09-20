<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1ekh8bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1ekh8bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mudslide-outline" {...props}></Icon>
