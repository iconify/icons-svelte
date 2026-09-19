<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u42uzwbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="u42uzwbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:map-o" {...props}></Icon>
