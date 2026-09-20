<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-0u1nyfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l-0u1nyfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book" {...props}></Icon>
