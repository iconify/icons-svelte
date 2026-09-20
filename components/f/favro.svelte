<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tro9njgej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tro9njgej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:favro" {...props}></Icon>
