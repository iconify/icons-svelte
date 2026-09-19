<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu1x4xb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mu1x4xb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:buromobelexperte" {...props}></Icon>
