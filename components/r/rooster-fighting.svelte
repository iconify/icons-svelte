<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3t-ovr2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w3t-ovr2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rooster-fighting" {...props}></Icon>
