<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2djpbfz.css';
import '../../css/m/m1or6kb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="m1or6kb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-full-20-bold" {...props}></Icon>
