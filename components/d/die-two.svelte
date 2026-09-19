<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyjrc407i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gyjrc407i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:die-two" {...props}></Icon>
