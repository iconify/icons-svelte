<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eicqy9tnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="eicqy9tnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:clinic-medical" {...props}></Icon>
