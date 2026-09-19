<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdtz0m5lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zdtz0m5lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:poo-storm" {...props}></Icon>
