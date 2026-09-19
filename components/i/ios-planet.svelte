<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-33augld.css';
import '../../css/b/bxfwu8b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-33augld"/><path class="bxfwu8b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-planet" {...props}></Icon>
