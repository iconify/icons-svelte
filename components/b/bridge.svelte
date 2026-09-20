<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsx_xhbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsx_xhbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bridge" {...props}></Icon>
