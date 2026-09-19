<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-4lsb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ld-4lsb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mostly-cloudy" {...props}></Icon>
