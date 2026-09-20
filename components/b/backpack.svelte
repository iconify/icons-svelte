<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r58q7ybvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r58q7ybvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:backpack" {...props}></Icon>
