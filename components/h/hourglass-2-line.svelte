<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ric7uy4wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ric7uy4wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hourglass-2-line" {...props}></Icon>
