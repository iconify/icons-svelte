<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiqmxbz-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xiqmxbz-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:fonticons-fi" {...props}></Icon>
