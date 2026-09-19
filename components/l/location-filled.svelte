<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emu51xc3a.css';
import '../../css/g/gblnhkdce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="emu51xc3a"/><circle class="gblnhkdce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-filled" {...props}></Icon>
