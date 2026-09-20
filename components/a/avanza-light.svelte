<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1sukl-mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1549,"height":1881};
const content = `<path class="f1sukl-mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avanza-light" {...props}></Icon>
