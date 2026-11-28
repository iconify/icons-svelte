<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rohs4-bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rohs4-bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-heart" {...props}></Icon>
