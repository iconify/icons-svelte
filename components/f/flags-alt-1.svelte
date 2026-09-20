<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6y1o92sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="y6y1o92sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flags-alt-1" {...props}></Icon>
