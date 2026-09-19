<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4q0w21ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":496};
const content = `<path class="m4q0w21ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:crown" {...props}></Icon>
