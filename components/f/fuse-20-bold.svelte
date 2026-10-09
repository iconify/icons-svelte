<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4d61mpoq.css';
import '../../css/l/l0042n2sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4d61mpoq"/><path class="l0042n2sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuse-20-bold" {...props}></Icon>
