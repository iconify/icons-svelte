<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kampcngpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kampcngpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fist-raised-solid" {...props}></Icon>
