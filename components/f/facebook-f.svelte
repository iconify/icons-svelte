<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy8y-8xfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fy8y-8xfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:facebook-f" {...props}></Icon>
