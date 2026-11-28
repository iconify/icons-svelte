<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut9c3ubur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut9c3ubur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:backpack" {...props}></Icon>
