<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7g_n0bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w7g_n0bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:attach-outline" {...props}></Icon>
