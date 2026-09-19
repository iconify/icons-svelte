<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_msvzj4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="h_msvzj4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chain" {...props}></Icon>
