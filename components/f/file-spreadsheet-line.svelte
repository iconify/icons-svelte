<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94hp_bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d94hp_bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-spreadsheet-line" {...props}></Icon>
