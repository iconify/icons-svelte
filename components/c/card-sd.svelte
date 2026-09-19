<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f963cdb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="f963cdb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-sd" {...props}></Icon>
