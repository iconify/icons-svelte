<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ju1lujl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="a3ju1lujl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-1" {...props}></Icon>
