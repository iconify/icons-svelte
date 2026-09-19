<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isb-9kkjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="isb-9kkjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pin" {...props}></Icon>
