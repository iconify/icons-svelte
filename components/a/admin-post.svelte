<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6jtdtbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y6jtdtbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-post" {...props}></Icon>
