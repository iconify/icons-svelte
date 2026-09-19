<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zryyp6ntt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="zryyp6ntt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:exclamation" {...props}></Icon>
