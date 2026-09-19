<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p26oc5e-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p26oc5e-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ice-cream" {...props}></Icon>
