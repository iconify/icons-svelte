<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6w9hdc9o.css';
import '../../css/p/pi1hrbbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p6w9hdc9o"/><path class="pi1hrbbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pizza-slice-20-bold" {...props}></Icon>
