<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3djeb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lw3djeb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:military" {...props}></Icon>
