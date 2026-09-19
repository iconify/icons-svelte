<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtwe9kb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vtwe9kb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cross-tab" {...props}></Icon>
