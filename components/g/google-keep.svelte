<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m22-05bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m22-05bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:google-keep" {...props}></Icon>
