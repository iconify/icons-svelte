<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eedsxqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eedsxqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pills-bold" {...props}></Icon>
