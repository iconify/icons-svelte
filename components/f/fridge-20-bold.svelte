<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkj4mhl3n.css';
import '../../css/p/p8l4h7b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkj4mhl3n"/><path class="p8l4h7b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fridge-20-bold" {...props}></Icon>
