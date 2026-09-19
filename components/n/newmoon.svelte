<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz-ie_bjg.css';
import '../../css/f/f9id0oq2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cz-ie_bjg"/><path class="f9id0oq2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:newmoon" {...props}></Icon>
