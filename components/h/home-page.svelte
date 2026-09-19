<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzdhhjb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yzdhhjb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:home-page" {...props}></Icon>
