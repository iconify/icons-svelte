<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2p81jij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pp2p81jij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:plus-square" {...props}></Icon>
