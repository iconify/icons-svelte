<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf1gocc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hf1gocc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cup-cake" {...props}></Icon>
