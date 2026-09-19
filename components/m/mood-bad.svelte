<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9r-peody.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="a9r-peody"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mood-bad" {...props}></Icon>
