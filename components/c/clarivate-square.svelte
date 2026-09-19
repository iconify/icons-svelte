<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdxhk8z_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fdxhk8z_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:clarivate-square" {...props}></Icon>
