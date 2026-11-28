<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc1y7ccgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc1y7ccgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coffee-star" {...props}></Icon>
