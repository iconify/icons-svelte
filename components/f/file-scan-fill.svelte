<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq170-bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq170-bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-scan-fill" {...props}></Icon>
