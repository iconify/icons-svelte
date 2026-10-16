<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzvlv_b9a.css';
import '../../css/y/yrnfbubdf.css';
import '../../css/l/lsfkntbhg.css';
import '../../css/h/h42_f1zpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nzvlv_b9a"/><path class="yrnfbubdf"/><path class="lsfkntbhg"/><path class="h42_f1zpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:church-20-bold" {...props}></Icon>
