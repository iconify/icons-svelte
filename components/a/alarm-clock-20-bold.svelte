<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnqtbnznq.css';
import '../../css/h/hq96i1lwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xnqtbnznq"/><path class="hq96i1lwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-20-bold" {...props}></Icon>
