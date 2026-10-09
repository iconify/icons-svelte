<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s71x42bul.css';
import '../../css/d/dutsueb3v.css';
import '../../css/y/ybedvpc_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s71x42bul"/><path class="dutsueb3v"/><path class="ybedvpc_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jack-up-vessel-20-bold" {...props}></Icon>
