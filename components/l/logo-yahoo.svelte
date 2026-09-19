<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2hg3jz1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k2hg3jz1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-yahoo" {...props}></Icon>
