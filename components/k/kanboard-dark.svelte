<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrso21bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrso21bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanboard-dark" {...props}></Icon>
