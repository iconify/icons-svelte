<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi2sbomcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fi2sbomcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-excited-fill-20" {...props}></Icon>
