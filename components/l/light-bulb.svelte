<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acxe7qz5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acxe7qz5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:light-bulb" {...props}></Icon>
