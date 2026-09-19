<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctp10hf8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ctp10hf8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bubble-message-dot-2" {...props}></Icon>
