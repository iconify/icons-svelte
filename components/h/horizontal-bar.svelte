<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfw4b_blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wfw4b_blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horizontal-bar" {...props}></Icon>
