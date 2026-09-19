<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrnc01brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vrnc01brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:eye-low-vision" {...props}></Icon>
