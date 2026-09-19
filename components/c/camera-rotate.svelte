<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftzq5d8pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ftzq5d8pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-rotate" {...props}></Icon>
