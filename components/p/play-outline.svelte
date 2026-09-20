<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6q78qbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6q78qbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:play-outline" {...props}></Icon>
