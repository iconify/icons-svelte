<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a37an34lq.css';
import '../../css/l/lkqfabbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a37an34lq"/><path class="lkqfabbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cheese-20-bold" {...props}></Icon>
