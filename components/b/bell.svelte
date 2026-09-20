<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0scjib0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p0scjib0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:bell" {...props}></Icon>
