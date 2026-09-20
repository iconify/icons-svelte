<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg-aufe2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gg-aufe2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:moon" {...props}></Icon>
