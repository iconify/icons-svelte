<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4w5s_mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wt4w5s_mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:overweight-person" {...props}></Icon>
