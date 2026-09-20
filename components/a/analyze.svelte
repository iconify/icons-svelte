<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruvfvnb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ruvfvnb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:analyze" {...props}></Icon>
