<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i374mtb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="i374mtb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:case" {...props}></Icon>
