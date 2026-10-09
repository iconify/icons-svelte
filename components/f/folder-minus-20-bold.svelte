<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u47_4yu8m.css';
import '../../css/o/oiw__zvyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u47_4yu8m"/><path class="oiw__zvyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-minus-20-bold" {...props}></Icon>
