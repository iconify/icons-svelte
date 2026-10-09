<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyg45n2yc.css';
import '../../css/h/htonzo4-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xyg45n2yc"/><path class="htonzo4-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopile-48-bold" {...props}></Icon>
