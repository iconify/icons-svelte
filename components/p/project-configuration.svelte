<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le2yqbc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le2yqbc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-configuration" {...props}></Icon>
