<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb_7g2bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vb_7g2bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:landmark-15" {...props}></Icon>
