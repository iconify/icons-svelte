<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf2faab1e.css';
import '../../css/c/czl4vwb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="czl4vwb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-3-line" {...props}></Icon>
