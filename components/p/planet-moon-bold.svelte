<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnmpmwbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gnmpmwbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:planet-moon-bold" {...props}></Icon>
