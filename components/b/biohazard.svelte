<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2x0b7bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="d2x0b7bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:biohazard" {...props}></Icon>
