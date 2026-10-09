<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfgcicctr.css';
import '../../css/l/lnhu_cben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="lnhu_cben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-6-20-bold" {...props}></Icon>
