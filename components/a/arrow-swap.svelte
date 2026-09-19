<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua1k4no5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1k4no5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-swap" {...props}></Icon>
