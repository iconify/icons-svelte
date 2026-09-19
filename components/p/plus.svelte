<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jicomkr5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="jicomkr5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:plus" {...props}></Icon>
