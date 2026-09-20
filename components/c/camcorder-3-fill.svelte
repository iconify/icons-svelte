<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sersdwbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sersdwbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-3-fill" {...props}></Icon>
