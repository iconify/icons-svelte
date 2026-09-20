<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9w93fb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p9w93fb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compact-box-truck" {...props}></Icon>
