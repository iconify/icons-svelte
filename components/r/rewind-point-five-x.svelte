<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn6i8jbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pn6i8jbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rewind-point-five-x" {...props}></Icon>
