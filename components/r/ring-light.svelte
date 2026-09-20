<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5b2u6byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5b2u6byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ring-light" {...props}></Icon>
