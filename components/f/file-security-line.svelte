<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7w7mpvun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7w7mpvun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-security-line" {...props}></Icon>
