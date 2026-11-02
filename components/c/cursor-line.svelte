<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gly0l3bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gly0l3bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-line" {...props}></Icon>
