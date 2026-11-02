<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwy2i44ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy2i44ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beer-off-line" {...props}></Icon>
