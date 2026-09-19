<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ykkg6js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5ykkg6js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:list-numbered-rtl" {...props}></Icon>
