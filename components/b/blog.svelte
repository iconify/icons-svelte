<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7hmxrbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7hmxrbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:blog" {...props}></Icon>
