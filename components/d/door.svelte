<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgbdwlrnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgbdwlrnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:door" {...props}></Icon>
