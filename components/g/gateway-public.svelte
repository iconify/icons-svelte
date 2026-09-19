<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnz2qsb9e.css';
import '../../css/j/j8yh1x58g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vnz2qsb9e"/><path class="j8yh1x58g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gateway-public" {...props}></Icon>
