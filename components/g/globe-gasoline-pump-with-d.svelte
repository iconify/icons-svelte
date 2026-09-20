<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2qdo2_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ny2qdo2_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:globe-gasoline-pump-with-d" {...props}></Icon>
