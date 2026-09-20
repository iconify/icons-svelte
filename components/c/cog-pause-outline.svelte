<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftewb93xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftewb93xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-pause-outline" {...props}></Icon>
