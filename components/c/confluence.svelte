<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvux2i21t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mvux2i21t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:confluence" {...props}></Icon>
