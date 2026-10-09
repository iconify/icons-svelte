<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp6stzr0z.css';
import '../../css/r/r8mpjxb7m.css';
import '../../css/l/ltpo7s9_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dp6stzr0z"/><path class="r8mpjxb7m"/><path class="ltpo7s9_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feed-in-20-bold" {...props}></Icon>
