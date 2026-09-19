<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8s2d0bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8s2d0bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hospital-fill" {...props}></Icon>
