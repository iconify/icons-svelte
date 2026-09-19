<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dth_nabga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dth_nabga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:greater-than-equal" {...props}></Icon>
