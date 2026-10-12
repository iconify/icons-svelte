<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz-qfmbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oz-qfmbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rescue-ring-fill-20" {...props}></Icon>
