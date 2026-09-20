<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4d9uq82f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y4d9uq82f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:crosshairs-solid" {...props}></Icon>
