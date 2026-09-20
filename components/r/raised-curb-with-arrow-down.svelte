<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u_5ebdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k2u_5ebdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:raised-curb-with-arrow-down" {...props}></Icon>
