<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-vny2gon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h-vny2gon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-car-outline" {...props}></Icon>
