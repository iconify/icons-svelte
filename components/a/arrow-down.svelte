<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp1sjjb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gp1sjjb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:arrow-down" {...props}></Icon>
