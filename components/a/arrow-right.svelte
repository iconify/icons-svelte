<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruef20b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ruef20b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-right" {...props}></Icon>
