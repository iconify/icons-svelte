<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afo943bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="afo943bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-grocery-store" {...props}></Icon>
