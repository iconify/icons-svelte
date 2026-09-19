<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfqwesb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfqwesb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:babys-room" {...props}></Icon>
