<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vabbgtf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vabbgtf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mattress-pillow" {...props}></Icon>
