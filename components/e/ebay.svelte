<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgwa1-1-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgwa1-1-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ebay" {...props}></Icon>
