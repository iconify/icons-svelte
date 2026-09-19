<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nib59ubmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nib59ubmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloudy" {...props}></Icon>
