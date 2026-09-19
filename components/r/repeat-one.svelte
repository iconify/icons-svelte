<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfz3hpbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="rfz3hpbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:repeat-one" {...props}></Icon>
