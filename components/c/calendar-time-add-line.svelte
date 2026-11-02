<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3wdkibzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3wdkibzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-time-add-line" {...props}></Icon>
