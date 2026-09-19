<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m420mflov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="m420mflov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:check-square" {...props}></Icon>
