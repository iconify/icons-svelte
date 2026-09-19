<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa-f7x0yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xa-f7x0yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hand-left" {...props}></Icon>
