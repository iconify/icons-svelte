<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5vguepc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hm5vguepc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:osf" {...props}></Icon>
