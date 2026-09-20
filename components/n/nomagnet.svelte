<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5uod30j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zm5uod30j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:nomagnet" {...props}></Icon>
