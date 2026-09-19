<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np9ruzbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="np9ruzbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:magic-wand-filled" {...props}></Icon>
