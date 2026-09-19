<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll1cpmbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ll1cpmbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bitdefender" {...props}></Icon>
