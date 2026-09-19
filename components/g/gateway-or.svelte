<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogk-g9bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ogk-g9bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:gateway-or" {...props}></Icon>
