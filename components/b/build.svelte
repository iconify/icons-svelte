<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3eb5-b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3eb5-b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:build" {...props}></Icon>
