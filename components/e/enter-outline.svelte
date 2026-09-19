<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d27bhtbqq.css';
import '../../css/v/v0283z18f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d27bhtbqq"/><path class="v0283z18f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:enter-outline" {...props}></Icon>
