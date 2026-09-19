<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azhh47bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="azhh47bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:behance-square" {...props}></Icon>
