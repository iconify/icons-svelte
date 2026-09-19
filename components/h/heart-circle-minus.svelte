<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8h25poui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t8h25poui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:heart-circle-minus" {...props}></Icon>
