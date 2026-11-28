<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3n7myzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-3n7myzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coins" {...props}></Icon>
