<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0jfyji9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="z0jfyji9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:balance" {...props}></Icon>
