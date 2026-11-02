<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctd_733kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd_733kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-chart-column-fill" {...props}></Icon>
