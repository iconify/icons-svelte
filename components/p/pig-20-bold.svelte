<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbyolzb7w.css';
import '../../css/b/byv6wwb2b.css';
import '../../css/r/rv2qj4l3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cbyolzb7w"/><path class="byv6wwb2b"/><path class="rv2qj4l3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pig-20-bold" {...props}></Icon>
