<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cte1i0tye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cte1i0tye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:female-groin" {...props}></Icon>
