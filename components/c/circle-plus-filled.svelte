<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_fy5bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e6_fy5bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:circle-plus-filled" {...props}></Icon>
