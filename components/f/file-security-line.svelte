<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap50jdwsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap50jdwsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-security-line" {...props}></Icon>
