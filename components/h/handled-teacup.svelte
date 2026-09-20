<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sen0zg3ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sen0zg3ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:handled-teacup" {...props}></Icon>
