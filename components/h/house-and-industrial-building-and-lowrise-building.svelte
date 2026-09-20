<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq5m95a3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mq5m95a3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:house-and-industrial-building-and-lowrise-building" {...props}></Icon>
