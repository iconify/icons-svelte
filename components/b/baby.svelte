<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_no2n83c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p_no2n83c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:baby" {...props}></Icon>
