<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1r5bbcod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1r5bbcod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anytype-light" {...props}></Icon>
