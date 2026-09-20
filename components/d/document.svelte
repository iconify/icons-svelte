<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxxquib2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxxquib2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document" {...props}></Icon>
