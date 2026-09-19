<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/g/gg8as3g9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="gg8as3g9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:compass-outline" {...props}></Icon>
