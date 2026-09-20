<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2_ki8_mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2_ki8_mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-box-ai-line" {...props}></Icon>
