<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4waorgjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z4waorgjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:magnet" {...props}></Icon>
