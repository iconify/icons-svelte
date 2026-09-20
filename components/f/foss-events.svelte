<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2fefzbda.css';
import '../../css/t/ttor7fbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2fefzbda"/><path class="ttor7fbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:foss-events" {...props}></Icon>
