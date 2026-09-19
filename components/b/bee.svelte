<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd-seobce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kd-seobce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bee" {...props}></Icon>
