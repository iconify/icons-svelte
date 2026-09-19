<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctpz6c3qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctpz6c3qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pencil" {...props}></Icon>
