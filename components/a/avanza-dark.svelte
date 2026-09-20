<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok0f7lvom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1549,"height":1881};
const content = `<path class="ok0f7lvom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avanza-dark" {...props}></Icon>
