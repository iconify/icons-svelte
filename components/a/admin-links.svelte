<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei08f3b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ei08f3b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-links" {...props}></Icon>
