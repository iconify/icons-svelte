<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94jikbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d94jikbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:db" {...props}></Icon>
