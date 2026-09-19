<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jar0caccs.css';
import '../../css/l/loy56xi0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jar0caccs"/><path class="loy56xi0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-right-01-filled" {...props}></Icon>
