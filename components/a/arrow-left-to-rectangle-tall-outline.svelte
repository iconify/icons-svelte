<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec3vx5m2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ec3vx5m2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-left-to-rectangle-tall-outline" {...props}></Icon>
