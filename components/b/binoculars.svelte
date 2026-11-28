<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdg_nsbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdg_nsbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:binoculars" {...props}></Icon>
