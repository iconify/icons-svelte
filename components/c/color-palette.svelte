<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw4sg4bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dw4sg4bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:color-palette" {...props}></Icon>
