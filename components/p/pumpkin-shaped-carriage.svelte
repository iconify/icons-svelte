<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_s1dyepv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_s1dyepv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pumpkin-shaped-carriage" {...props}></Icon>
