<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqvu_8b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uqvu_8b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-right" {...props}></Icon>
