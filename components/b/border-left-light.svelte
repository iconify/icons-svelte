<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lybym4bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lybym4bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-left-light" {...props}></Icon>
