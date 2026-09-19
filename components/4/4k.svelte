<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izq05d10w.css';
import '../../css/h/hezf90bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="izq05d10w"/><path class="hezf90bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:4k" {...props}></Icon>
