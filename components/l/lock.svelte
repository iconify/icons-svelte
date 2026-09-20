<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lff1pxbum.css';
import '../../css/j/jd3246bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lff1pxbum"/><path class="jd3246bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:lock" {...props}></Icon>
