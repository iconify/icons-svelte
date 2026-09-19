<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1ignf9pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="u1ignf9pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:piggy-bank" {...props}></Icon>
