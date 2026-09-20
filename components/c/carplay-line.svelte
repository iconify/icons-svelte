<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tch096bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tch096bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:carplay-line" {...props}></Icon>
