<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpmv17cfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpmv17cfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:broadcast-tower-solid" {...props}></Icon>
