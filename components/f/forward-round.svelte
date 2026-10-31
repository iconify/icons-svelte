<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrk0z1wmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrk0z1wmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:forward-round" {...props}></Icon>
