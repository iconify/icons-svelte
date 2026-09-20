<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfqbixbqc.css';
import '../../css/p/pxh-139-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bfqbixbqc"/><path clip-rule="evenodd" class="pxh-139-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:browser-website-1-solid" {...props}></Icon>
