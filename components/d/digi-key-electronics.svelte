<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7vi-tn5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7vi-tn5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:digi-key-electronics" {...props}></Icon>
