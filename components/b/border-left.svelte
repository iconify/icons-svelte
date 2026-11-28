<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du-n6bmny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="du-n6bmny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-left" {...props}></Icon>
