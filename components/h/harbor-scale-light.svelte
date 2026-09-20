<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktq9-0qkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ktq9-0qkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-scale-light" {...props}></Icon>
