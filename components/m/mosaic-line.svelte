<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgq3h-um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgq3h-um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mosaic-line" {...props}></Icon>
