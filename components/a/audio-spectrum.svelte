<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3n3ghbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r3n3ghbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:audio-spectrum" {...props}></Icon>
