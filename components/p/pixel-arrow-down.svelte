<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzfh-ubpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zzfh-ubpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrow-down" {...props}></Icon>
