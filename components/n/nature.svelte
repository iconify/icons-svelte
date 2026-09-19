<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i23y3acgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":432};
const content = `<path class="i23y3acgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:nature" {...props}></Icon>
