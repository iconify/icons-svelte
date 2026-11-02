<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4bg2m00a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4bg2m00a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bold-line" {...props}></Icon>
