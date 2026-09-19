<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rw8bc3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x1rw8bc3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pager" {...props}></Icon>
