<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6feaxw3l.css';
import '../../css/g/gx0j_wt-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w6feaxw3l"/><path class="gx0j_wt-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:media-library-filled" {...props}></Icon>
