<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfnz8351n.css';
import '../../css/y/y8mkib1ak.css';
import '../../css/r/rs7rz-b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfnz8351n"/><circle class="y8mkib1ak"/><path class="rs7rz-b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bare-metal-server-01" {...props}></Icon>
