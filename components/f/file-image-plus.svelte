<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frt9vwbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frt9vwbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-image-plus" {...props}></Icon>
