<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv3_5ob-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cv3_5ob-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:napster" {...props}></Icon>
