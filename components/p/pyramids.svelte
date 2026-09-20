<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8z2b9b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="j8z2b9b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pyramids" {...props}></Icon>
