<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5v5b0u5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5v5b0u5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-time" {...props}></Icon>
