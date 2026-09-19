<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db9fy1bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="db9fy1bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path-rounded-square-20-solid" {...props}></Icon>
