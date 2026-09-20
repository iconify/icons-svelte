<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4phf5orn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k4phf5orn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:envelope-open-text-solid" {...props}></Icon>
