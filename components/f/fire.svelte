<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtlu3wbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xtlu3wbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:fire" {...props}></Icon>
