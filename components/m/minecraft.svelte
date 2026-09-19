<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpfxdab7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hpfxdab7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:minecraft" {...props}></Icon>
