<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx32ncc0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kx32ncc0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bunker" {...props}></Icon>
