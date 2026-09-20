<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izt10ctsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izt10ctsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:isro" {...props}></Icon>
