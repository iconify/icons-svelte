<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7nbqy7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lu7nbqy7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:copy-check-light" {...props}></Icon>
