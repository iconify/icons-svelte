<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0h42yj7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0h42yj7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:home-2" {...props}></Icon>
