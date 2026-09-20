<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myp90-ogc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="myp90-ogc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hotdog-solid" {...props}></Icon>
