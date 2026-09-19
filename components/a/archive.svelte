<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1y_4bigl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="f1y_4bigl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:archive" {...props}></Icon>
