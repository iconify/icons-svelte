<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou2fv_0vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ou2fv_0vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-exclamation-point" {...props}></Icon>
