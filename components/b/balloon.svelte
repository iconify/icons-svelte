<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5os10bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="m5os10bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:balloon" {...props}></Icon>
