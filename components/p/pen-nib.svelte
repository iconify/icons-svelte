<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb5-vgbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tb5-vgbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pen-nib" {...props}></Icon>
