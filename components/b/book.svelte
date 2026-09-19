<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e65cizbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e65cizbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:book" {...props}></Icon>
