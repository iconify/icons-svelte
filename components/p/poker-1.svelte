<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujm4itb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="ujm4itb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:poker-1" {...props}></Icon>
