<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btdsy2bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="btdsy2bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ahimsa-hand" {...props}></Icon>
