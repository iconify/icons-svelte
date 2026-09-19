<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5_b1pbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5_b1pbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-solid" {...props}></Icon>
