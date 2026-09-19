<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7dqhqbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7dqhqbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-download-outline" {...props}></Icon>
