<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9cng6v1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w9cng6v1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:n" {...props}></Icon>
