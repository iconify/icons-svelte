<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp7ukgblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pp7ukgblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bold" {...props}></Icon>
