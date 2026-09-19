<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrhl2piks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lrhl2piks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hourglass-split" {...props}></Icon>
