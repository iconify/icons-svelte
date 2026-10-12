<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpfsank0h.css';
import '../../css/u/uedqdgfhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lpfsank0h"/><path class="uedqdgfhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-stack-stroke-20" {...props}></Icon>
