<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr79zmb6s.css';
import '../../css/j/jdsu42b0b.css';
import '../../css/n/n412juyes.css';
import '../../css/v/vk54hubeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cr79zmb6s"/><circle class="jdsu42b0b"/><path class="n412juyes"/><path class="vk54hubeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cd-create-archive" {...props}></Icon>
