<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgb1gcbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgb1gcbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-takeoff-fill" {...props}></Icon>
