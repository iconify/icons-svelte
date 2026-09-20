<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9v4r7bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o9v4r7bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:euro-outline" {...props}></Icon>
