<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk7pu-57w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rk7pu-57w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hospital" {...props}></Icon>
