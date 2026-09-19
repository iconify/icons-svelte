<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5sg82bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5sg82bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fade" {...props}></Icon>
