<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh7ee76kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bh7ee76kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:firefox" {...props}></Icon>
