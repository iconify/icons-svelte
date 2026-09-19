<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5zi9c24n.css';
import '../../css/j/ji_uifbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5zi9c24n"/><path class="ji_uifbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:location-on" {...props}></Icon>
