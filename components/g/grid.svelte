<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7hn-9ncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="a7hn-9ncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:grid" {...props}></Icon>
