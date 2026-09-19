<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar7ya4bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ar7ya4bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:quote-open" {...props}></Icon>
