<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3343rbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3343rbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatorp" {...props}></Icon>
