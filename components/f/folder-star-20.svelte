<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3me-4caq.css';
import '../../css/r/rr-f5tb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="rr-f5tb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-star-20" {...props}></Icon>
