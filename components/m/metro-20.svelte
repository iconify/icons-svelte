<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlyagw35s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dlyagw35s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:metro-20" {...props}></Icon>
