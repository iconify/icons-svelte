<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8wvdtb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j8wvdtb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mouse-solid" {...props}></Icon>
