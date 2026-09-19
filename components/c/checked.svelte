<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6tv7ib_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="j6tv7ib_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:checked" {...props}></Icon>
