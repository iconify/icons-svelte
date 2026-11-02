<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq_4vpbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq_4vpbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-download-line" {...props}></Icon>
