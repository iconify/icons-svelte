<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1-6s-b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1-6s-b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:document-3" {...props}></Icon>
