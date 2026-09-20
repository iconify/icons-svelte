<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9yg-6b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9yg-6b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:palette-filled" {...props}></Icon>
