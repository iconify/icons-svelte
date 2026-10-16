<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2djpbfz.css';
import '../../css/u/uylaeij1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="uylaeij1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-half-20-bold" {...props}></Icon>
