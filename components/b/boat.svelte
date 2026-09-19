<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci1k7zbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ci1k7zbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:boat" {...props}></Icon>
