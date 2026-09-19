<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmbxpg-wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dmbxpg-wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pin-angle-fill" {...props}></Icon>
