<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7e65b99l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="y7e65b99l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bubble-message-dot" {...props}></Icon>
