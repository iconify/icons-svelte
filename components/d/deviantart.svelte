<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwo7qkb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="jwo7qkb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:deviantart" {...props}></Icon>
