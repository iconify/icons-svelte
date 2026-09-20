<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1hic9yix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k1hic9yix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:handshake" {...props}></Icon>
