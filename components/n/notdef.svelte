<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxu-7-bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="nxu-7-bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:notdef" {...props}></Icon>
