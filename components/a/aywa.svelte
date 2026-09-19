<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbbxf8-7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sbbxf8-7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:aywa" {...props}></Icon>
