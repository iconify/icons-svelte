<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl24qvkai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl24qvkai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-rain-line" {...props}></Icon>
