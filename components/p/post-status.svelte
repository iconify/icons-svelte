<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uil913pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uil913pbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:post-status" {...props}></Icon>
