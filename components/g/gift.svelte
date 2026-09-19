<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6l78ybxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6l78ybxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:gift" {...props}></Icon>
