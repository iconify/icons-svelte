<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3q3sr33k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x3q3sr33k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-yen-yuan" {...props}></Icon>
