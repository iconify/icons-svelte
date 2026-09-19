<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh5b57bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xh5b57bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:navigate-circle" {...props}></Icon>
