<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_blhsbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x_blhsbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-exclamation-point" {...props}></Icon>
