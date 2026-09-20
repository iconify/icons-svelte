<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu1ar6dsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tu1ar6dsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fandom" {...props}></Icon>
