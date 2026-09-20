<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3f8bglu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vz3f8bglu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:diving" {...props}></Icon>
