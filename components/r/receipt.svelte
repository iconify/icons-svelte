<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e25-plskk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="e25-plskk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:receipt" {...props}></Icon>
