<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po5zkhctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="po5zkhctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mixer" {...props}></Icon>
