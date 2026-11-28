<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicvamyrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xicvamyrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:refresh" {...props}></Icon>
