<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zum3w4bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zum3w4bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:favorite-filled" {...props}></Icon>
