<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdresjymm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xdresjymm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rocking-horse" {...props}></Icon>
