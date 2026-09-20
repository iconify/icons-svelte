<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw5a7nblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bw5a7nblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bowling-ball" {...props}></Icon>
