<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbps0obhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qbps0obhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parallelogram-tall-left" {...props}></Icon>
