<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq2yzttin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rq2yzttin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heading-1-paragraph-styles-heading" {...props}></Icon>
