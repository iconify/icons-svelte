<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn4vx2bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jn4vx2bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:road-circle-xmark" {...props}></Icon>
