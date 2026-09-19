<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcqgukb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vcqgukb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:reddit" {...props}></Icon>
