<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xylbu51th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xylbu51th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dharma-wheel" {...props}></Icon>
