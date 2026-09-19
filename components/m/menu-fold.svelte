<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twr408bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="twr408bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:menu-fold" {...props}></Icon>
