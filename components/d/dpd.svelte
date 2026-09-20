<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct65_nbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct65_nbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dpd" {...props}></Icon>
