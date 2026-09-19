<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsd1mab5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rsd1mab5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropright-circle" {...props}></Icon>
