<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq5s4xbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq5s4xbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fence-filled" {...props}></Icon>
