<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flw1gabej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flw1gabej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-low-fill-round" {...props}></Icon>
