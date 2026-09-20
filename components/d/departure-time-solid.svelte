<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3n4l6bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z3n4l6bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:departure-time-solid" {...props}></Icon>
