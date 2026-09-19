<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2l6rf1jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2l6rf1jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bandage" {...props}></Icon>
