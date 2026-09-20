<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5fjp5z7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5fjp5z7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bilibili-index-index-team" {...props}></Icon>
