<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4k4l6b7c.css';
import '../../css/a/aa6fczbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4k4l6b7c"/><path class="aa6fczbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-link" {...props}></Icon>
