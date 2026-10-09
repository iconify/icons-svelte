<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9qjnk78v.css';
import '../../css/j/jsw558btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9qjnk78v"/><path class="jsw558btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milestone-20-bold" {...props}></Icon>
