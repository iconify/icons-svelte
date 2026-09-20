<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1-5inbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":85,"height":107};
const content = `<path class="w1-5inbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:astro-light" {...props}></Icon>
