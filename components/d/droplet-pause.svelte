<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frqrtvifx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frqrtvifx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-pause" {...props}></Icon>
