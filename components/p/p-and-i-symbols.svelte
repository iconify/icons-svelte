<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egumi9b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egumi9b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:p-and-i-symbols" {...props}></Icon>
