<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jabkixbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jabkixbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linejoin-miter-filled" {...props}></Icon>
