<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-3m1rb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="i-3m1rb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:play-circle" {...props}></Icon>
