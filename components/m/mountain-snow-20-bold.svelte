<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aghjl2bmp.css';
import '../../css/i/ic8mjabnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aghjl2bmp"/><path class="ic8mjabnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-snow-20-bold" {...props}></Icon>
