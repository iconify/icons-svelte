<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x58p07ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x58p07ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:lightbulb-dashed" {...props}></Icon>
