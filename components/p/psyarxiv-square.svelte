<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5rwvjb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p5rwvjb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:psyarxiv-square" {...props}></Icon>
