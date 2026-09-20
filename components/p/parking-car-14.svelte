<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8pkx9ste.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y8pkx9ste"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:parking-car-14" {...props}></Icon>
