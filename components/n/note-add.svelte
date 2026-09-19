<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3ke734ah.css';
import '../../css/z/zagwqcton.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3ke734ah"/><path class="zagwqcton"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:note-add" {...props}></Icon>
