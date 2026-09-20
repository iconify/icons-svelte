<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1h3x_ruo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k1h3x_ruo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pumpkin-under-stardust" {...props}></Icon>
