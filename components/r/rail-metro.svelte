<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnjapb-yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tnjapb-yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rail-metro" {...props}></Icon>
