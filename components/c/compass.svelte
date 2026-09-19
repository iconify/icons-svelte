<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t42fs85ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="t42fs85ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:compass" {...props}></Icon>
