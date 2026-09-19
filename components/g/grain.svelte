<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3pwlbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vm3pwlbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:grain" {...props}></Icon>
