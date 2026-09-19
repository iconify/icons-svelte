<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdc6cpb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdc6cpb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:library-building" {...props}></Icon>
