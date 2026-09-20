<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgm_8n2wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgm_8n2wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:piechart-ai-filled" {...props}></Icon>
