<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-a__rbow.css';
import '../../css/l/lppl2sbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-a__rbow"/><path class="lppl2sbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-objects" {...props}></Icon>
