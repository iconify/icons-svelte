<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv6mozbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv6mozbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:headphones-off" {...props}></Icon>
