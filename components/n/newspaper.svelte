<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcunpjb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcunpjb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:newspaper" {...props}></Icon>
