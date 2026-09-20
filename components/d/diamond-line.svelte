<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbt6qobfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbt6qobfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:diamond-line" {...props}></Icon>
