<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ny6yqxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="x8ny6yqxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:baby-troller" {...props}></Icon>
