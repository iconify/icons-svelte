<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seob3mb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="seob3mb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-stacked" {...props}></Icon>
