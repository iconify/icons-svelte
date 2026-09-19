<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv1jkn-1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv1jkn-1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:movie" {...props}></Icon>
