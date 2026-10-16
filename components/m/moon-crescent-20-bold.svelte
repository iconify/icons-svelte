<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2djpbfz.css';
import '../../css/p/p2ofzxv5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="p2ofzxv5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-crescent-20-bold" {...props}></Icon>
