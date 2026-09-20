<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brk4pcs8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="brk4pcs8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:compass-16" {...props}></Icon>
