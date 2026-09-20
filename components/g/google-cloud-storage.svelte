<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5-q460ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5-q460ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-cloud-storage" {...props}></Icon>
