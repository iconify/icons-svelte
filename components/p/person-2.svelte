<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asuv-oy1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="asuv-oy1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:person-2" {...props}></Icon>
