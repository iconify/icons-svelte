<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0rnk_b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g0rnk_b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microscope-outline" {...props}></Icon>
