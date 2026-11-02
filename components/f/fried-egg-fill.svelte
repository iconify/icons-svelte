<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhf85sbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhf85sbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fried-egg-fill" {...props}></Icon>
