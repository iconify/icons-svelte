<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4paek0_x.css';
import '../../css/l/lppl2sbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4paek0_x"/><path class="lppl2sbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-objects-new" {...props}></Icon>
