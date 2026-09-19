<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_i50-b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_i50-b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:coffee-cup" {...props}></Icon>
