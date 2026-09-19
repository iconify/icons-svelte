<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5zb4-b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a5zb4-b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clothes-gloves-two" {...props}></Icon>
