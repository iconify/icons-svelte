<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ys6h5qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b1ys6h5qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:confused-face" {...props}></Icon>
