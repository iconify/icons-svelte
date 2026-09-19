<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g543_ly2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="g543_ly2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:burn" {...props}></Icon>
