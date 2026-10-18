<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8u_2aczb.css';
import '../../css/t/t8o25qn7d.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8u_2aczb"/><path class="t8o25qn7d"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hedgerow-20-bold" {...props}></Icon>
