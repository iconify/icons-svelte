<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mcems0k.css';
import '../../css/r/rtxe8yjtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="rtxe8yjtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-thermometer-20-bold" {...props}></Icon>
