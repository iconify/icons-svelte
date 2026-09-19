<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z80pyoh0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z80pyoh0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-frown-open" {...props}></Icon>
