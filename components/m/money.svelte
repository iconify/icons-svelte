<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igz9ekoxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="igz9ekoxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:money" {...props}></Icon>
