<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ig2cc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="e6ig2cc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:close-circle" {...props}></Icon>
