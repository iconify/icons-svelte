<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuk26wbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="iuk26wbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:audio" {...props}></Icon>
