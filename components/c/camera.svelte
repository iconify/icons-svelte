<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq-fvwbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="vq-fvwbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:camera" {...props}></Icon>
