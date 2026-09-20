<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luc9fcg6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luc9fcg6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-line-solid" {...props}></Icon>
