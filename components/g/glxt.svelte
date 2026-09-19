<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oew13ew-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oew13ew-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:glxt" {...props}></Icon>
