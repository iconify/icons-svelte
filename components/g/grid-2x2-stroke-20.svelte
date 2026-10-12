<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt1lx2bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tt1lx2bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-2x2-stroke-20" {...props}></Icon>
