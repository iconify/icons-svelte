<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2j9s7bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p2j9s7bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:imdb" {...props}></Icon>
