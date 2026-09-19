<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg5au16ih.css';
import '../../css/m/mrndicbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tg5au16ih"/><path class="mrndicbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ice-vision" {...props}></Icon>
