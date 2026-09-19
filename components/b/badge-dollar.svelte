<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7fgw7bls.css';
import '../../css/y/yua1kc2gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7fgw7bls"/><path class="yua1kc2gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:badge-dollar" {...props}></Icon>
