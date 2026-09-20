<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vve01yrsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vve01yrsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-fonts" {...props}></Icon>
