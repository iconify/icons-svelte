<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uln5-cbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uln5-cbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-up-right" {...props}></Icon>
