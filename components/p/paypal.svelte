<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfneizbci.css';
import '../../css/g/g81nz19ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vfneizbci"/><path class="g81nz19ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:paypal" {...props}></Icon>
