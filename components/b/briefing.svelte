<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0w2mtbgl.css';
import '../../css/t/tl1zu4bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0w2mtbgl"/><path class="tl1zu4bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:briefing" {...props}></Icon>
