<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo7nucb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oo7nucb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:qualcomm" {...props}></Icon>
