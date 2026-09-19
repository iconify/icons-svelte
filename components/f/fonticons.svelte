<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5s6drg7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x5s6drg7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:fonticons" {...props}></Icon>
