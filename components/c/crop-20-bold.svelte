<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs8-z_yps.css';
import '../../css/e/ezgqvohnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gs8-z_yps"/><path class="ezgqvohnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crop-20-bold" {...props}></Icon>
