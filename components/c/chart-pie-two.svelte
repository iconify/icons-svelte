<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8b-o5wtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8b-o5wtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-pie-two" {...props}></Icon>
