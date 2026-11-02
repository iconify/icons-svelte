<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3i909bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3i909bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-parking-off-fill" {...props}></Icon>
