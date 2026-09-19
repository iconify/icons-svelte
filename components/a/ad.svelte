<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1er8ya1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1er8ya1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ad" {...props}></Icon>
