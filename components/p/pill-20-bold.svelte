<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j66ia2m5n.css';
import '../../css/u/uuavj04rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j66ia2m5n"/><path class="uuavj04rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-20-bold" {...props}></Icon>
