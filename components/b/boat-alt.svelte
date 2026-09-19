<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9g27pb1k.css';
import '../../css/s/soed_umth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9g27pb1k"/><path class="soed_umth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:boat-alt" {...props}></Icon>
