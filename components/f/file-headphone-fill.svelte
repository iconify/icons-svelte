<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wod75ccvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wod75ccvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-headphone-fill" {...props}></Icon>
