<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8s82qb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8s82qb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-1" {...props}></Icon>
