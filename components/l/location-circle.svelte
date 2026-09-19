<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ubi3rny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x4ubi3rny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:location-circle" {...props}></Icon>
