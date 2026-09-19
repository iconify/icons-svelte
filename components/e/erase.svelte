<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysmh8gbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ysmh8gbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:erase" {...props}></Icon>
