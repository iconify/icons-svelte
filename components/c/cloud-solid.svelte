<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0m9t2hdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0m9t2hdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-solid" {...props}></Icon>
