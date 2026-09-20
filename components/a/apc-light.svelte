<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlg5nbb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xlg5nbb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apc-light" {...props}></Icon>
