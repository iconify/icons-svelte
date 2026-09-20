<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0w3icfad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g0w3icfad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:print" {...props}></Icon>
