<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw10q5bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="yw10q5bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:googleplus-rect" {...props}></Icon>
