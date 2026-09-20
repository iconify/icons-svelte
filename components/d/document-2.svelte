<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzfilpbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzfilpbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:document-2" {...props}></Icon>
