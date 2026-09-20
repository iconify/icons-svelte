<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx4wm_5bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nx4wm_5bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mountain-solid" {...props}></Icon>
