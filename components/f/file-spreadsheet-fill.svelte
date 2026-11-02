<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0swyr58j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0swyr58j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-spreadsheet-fill" {...props}></Icon>
