<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjh43p2th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rjh43p2th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:habitat-social-dark" {...props}></Icon>
