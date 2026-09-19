<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-js14bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-js14bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:hackerrank" {...props}></Icon>
