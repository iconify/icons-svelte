<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfeadtbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jfeadtbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bicycle" {...props}></Icon>
