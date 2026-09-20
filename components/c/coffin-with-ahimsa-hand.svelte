<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4mzv2b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g4mzv2b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-ahimsa-hand" {...props}></Icon>
